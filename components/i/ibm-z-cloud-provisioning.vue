<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs_bqebbh.css';
import '../../css/m/m3lxbjutz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zs_bqebbh"/><path class="m3lxbjutz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-z-cloud-provisioning" /></template>
