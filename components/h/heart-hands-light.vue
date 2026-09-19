<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mwp_oydnr.css';
import '../../css/x/x7fo1-u6w.css';
import '../../css/e/era4mkbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="mwp_oydnr"/><path clip-rule="evenodd" class="x7fo1-u6w"/><path class="era4mkbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:heart-hands-light" /></template>
