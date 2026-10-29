<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qtx3gwboz.css';
import '../../css/h/hw4w3wbpy.css';
import '../../css/c/c0jlas_ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qtx3gwboz"/><path class="hw4w3wbpy wm-k"/><path class="c0jlas_ay wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-bunny-sketch" /></template>
