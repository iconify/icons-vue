<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/g55efo6fc.css';
import '../../css/i/ihk0gabkp.css';
import '../../css/u/uraiyuf6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="g55efo6fc"/><path class="ihk0gabkp"/><path class="uraiyuf6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:briefcase" /></template>
