<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jpo7_pb2a.css';
import '../../css/l/l62d9fwog.css';
import '../../css/b/bz0iknbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jpo7_pb2a"/><path class="l62d9fwog"/><path class="bz0iknbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-bottom-linear" /></template>
