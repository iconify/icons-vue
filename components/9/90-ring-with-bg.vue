<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnis27-yq.css';
import '../../css/u/u-34oac9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnis27-yq"/><path class="u-34oac9y"><animateTransform attributeName="transform" dur="0.75s" repeatCount="indefinite" type="rotate" values="0 12 12;360 12 12"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:90-ring-with-bg" /></template>
