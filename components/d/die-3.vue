<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h14emmvzq.css';
import '../../css/c/cix91lbno.css';
import '../../css/h/hgh6cwwcv.css';
import '../../css/d/deryr5bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="h14emmvzq"/><rect class="cix91lbno"/><rect class="hgh6cwwcv"/><rect class="deryr5bon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:die-3" /></template>
