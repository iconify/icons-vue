<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/otizujbvg.css';
import '../../css/d/dmbuntb5b.css';
import '../../css/g/gxh6gnbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="otizujbvg"/><path class="dmbuntb5b"/><path class="gxh6gnbgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:drops-outline" /></template>
