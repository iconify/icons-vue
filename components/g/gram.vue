<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jpk7rbbjw.css';
import '../../css/e/efdwq-jsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g class="ft5dv1b6b"><path class="jpk7rbbjw"/><path class="efdwq-jsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gram" /></template>
