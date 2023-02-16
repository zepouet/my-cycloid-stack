module "instance" {
  source   = "./module-azure"
  env      = "${var.env}"
  customer = "${var.customer}"
  project  = "${var.project}"

  git_code_commit = "${var.git_code_commit}"
  git_code_repo   = "${var.git_code_repo}"

  resource_group_name = "${var.azure_resource_group_name}"
  subnet_id           = "8edccc9d-445b-4cfd-b65b-afc79cd1de6d"
  azure_location      = "${var.azure_location}"
  instance_type       = "Standard_DS1_v2"
}
