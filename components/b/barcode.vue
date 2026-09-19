<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rymohubio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rymohubio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:barcode" /></template>
