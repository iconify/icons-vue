<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sssou3bkf.css';
import '../../css/y/ybhu5ybua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sssou3bkf"/><path class="ybhu5ybua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pal" /></template>
