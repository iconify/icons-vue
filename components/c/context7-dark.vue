<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r05ofdc8m.css';
import '../../css/m/mhqfye0oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<g class="ft5dv1b6b"><rect class="r05ofdc8m"/><path class="mhqfye0oj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:context7-dark" /></template>
