<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkxlcrb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rkxlcrb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-json-fill" /></template>
