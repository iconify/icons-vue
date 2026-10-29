<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n10sul64d.css';
import '../../css/n/n-z7qpbzg.css';
import '../../css/p/psnkz2bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n10sul64d"/><path class="n-z7qpbzg wm-a"/><path class="psnkz2bcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:camera-duo" /></template>
