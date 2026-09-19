<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oco214bjy.css';
import '../../css/z/zn9e1jbzm.css';
import '../../css/e/esmk_ibwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="oco214bjy"/><path class="zn9e1jbzm"/><path class="esmk_ibwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:envelope-front" /></template>
