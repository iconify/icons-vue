<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx8y2ds-k.css';
import '../../css/q/qfh1dz3dh.css';
import '../../css/d/denxdxots.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="qfh1dz3dh"/><path class="denxdxots"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:align-top" /></template>
