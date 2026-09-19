<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bgxfxxbfa.css';
import '../../css/d/dlzwfk8ub.css';
import '../../css/y/y1wcivbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bgxfxxbfa"/><path class="dlzwfk8ub"/><path class="y1wcivbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:exclude-bold" /></template>
