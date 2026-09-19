<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urjbm3bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="urjbm3bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-webmethods-hybrid-integration" /></template>
