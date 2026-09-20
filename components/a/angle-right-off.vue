<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kz4gazbfr.css';
import '../../css/y/ypxup6b3j.css';
import '../../css/o/ov7upw0qn.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="kz4gazbfr"/><path class="ypxup6b3j"/><path class="ov7upw0qn"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:angle-right-off" /></template>
