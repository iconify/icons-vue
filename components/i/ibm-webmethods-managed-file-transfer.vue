<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzf-sabyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yzf-sabyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-webmethods-managed-file-transfer" /></template>
