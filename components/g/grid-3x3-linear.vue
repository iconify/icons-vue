<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gaey7fiif.css';
import '../../css/a/a6wvo-b3o.css';
import '../../css/j/jojyntb-y.css';
import '../../css/z/ztzrfkqqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gaey7fiif"/><path class="a6wvo-b3o"/><path class="jojyntb-y"/><path class="ztzrfkqqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-3x3-linear" /></template>
