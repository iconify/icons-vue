<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/okusuaboz.css';
import '../../css/m/msynidc3r.css';
import '../../css/l/lzsxj9r9o.css';
import '../../css/r/r7k_16bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="okusuaboz"/><path class="msynidc3r wm-k"/><path class="lzsxj9r9o wm-k"/><path class="r7k_16bhv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:key-round-sketch" /></template>
