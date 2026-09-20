<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx5d-bc1s.css';
import '../../css/g/g2v-e666n.css';
import '../../css/w/w5gr3vtml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<g class="nx5d-bc1s"><path class="g2v-e666n"/><path class="w5gr3vtml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dailydotdev-dark" /></template>
