<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlzul8kzr.css';
import '../../css/s/sw83ssb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zlzul8kzr"/><path class="sw83ssb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bar-chart-square-stroke-20" /></template>
