<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv09d5sem.css';
import '../../css/g/gc0lb3cvd.css';
import '../../css/y/ytd8-zwcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456.8,"height":511.82,"left":27.6,"top":0.18};
const content = `<g class="dv09d5sem"><path class="gc0lb3cvd"/><path class="ytd8-zwcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jackett" /></template>
