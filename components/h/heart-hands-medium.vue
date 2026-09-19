<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pny3j9blh.css';
import '../../css/q/qczzyabmn.css';
import '../../css/i/i4kg29big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="pny3j9blh"/><path clip-rule="evenodd" class="qczzyabmn"/><path class="i4kg29big"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:heart-hands-medium" /></template>
