<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":271};
const content = `<path class="pdh_1eb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:hashicorp-icon" /></template>
<style>
.pdh_1eb2g {
  d: path("M215.907 38.502L256 61.648v147.837l-106.71 61.564v-46.236l66.617-38.474zM149.289 0l40.093 23.146V174.11l-40.093 23.118v-43.64h-42.578v117.405l-40.093-23.202V96.94l40.093-23.146v43.946h42.578zm-42.578 0v46.236L40.093 84.71v147.837L0 209.401V61.564z");
}

</style>
