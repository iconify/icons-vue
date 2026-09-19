<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/ira41xb9p.css';
import '../../css/h/hwsal5q-o.css';
import '../../css/p/pljtn-4ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><ellipse class="ira41xb9p"/><circle class="hwsal5q-o"/><path class="pljtn-4ly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:globe-outline" /></template>
