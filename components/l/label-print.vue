<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/sfubw46ew.css';
import '../../css/x/xl7_gdfrs.css';
import '../../css/i/iljijccvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="h01tyzbfu"><path class="sfubw46ew"/><path class="xl7_gdfrs"/><circle transform="rotate(-45 6.95 7.38)" class="iljijccvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:label-print" /></template>
