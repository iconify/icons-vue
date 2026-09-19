<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/r/r35i2tbxi.css';
import '../../css/q/qthgv0dij.css';
import '../../css/i/i-7vcwsvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="r35i2tbxi"/><path class="qthgv0dij"/><path class="i-7vcwsvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:car-outline" /></template>
