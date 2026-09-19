<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bex8n1b-w.css';
import '../../css/h/hsrzeq-ig.css';
import '../../css/g/g_362tbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bex8n1b-w"/><path class="hsrzeq-ig"/><path class="g_362tbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-data-product-exchange" /></template>
