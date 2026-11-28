<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mty7vx8_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mty7vx8_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-xml" /></template>
