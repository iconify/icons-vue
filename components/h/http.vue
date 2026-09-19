<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tif8-1b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tif8-1b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:http" /></template>
