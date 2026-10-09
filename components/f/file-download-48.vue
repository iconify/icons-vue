<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dezwopb-j.css';
import '../../css/u/u8wp1qb3l.css';
import '../../css/z/zay6z3bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="u8wp1qb3l"/><path class="zay6z3bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-download-48" /></template>
