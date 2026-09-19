<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-_a-hbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m-_a-hbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:curved-line-solid" /></template>
