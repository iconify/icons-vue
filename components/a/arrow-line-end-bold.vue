<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m9gh2ac4j.css';
import '../../css/j/ju_626tpw.css';
import '../../css/q/q-vn-bcdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="m9gh2ac4j"/><path class="ju_626tpw"/><path class="q-vn-bcdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-line-end-bold" /></template>
