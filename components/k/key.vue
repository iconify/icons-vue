<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y5utmh9wq.css';
import '../../css/y/y6fz92bxe.css';
import '../../css/a/a3-4ixr3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="y5utmh9wq"/><path clip-rule="evenodd" class="y6fz92bxe"/><path clip-rule="evenodd" class="a3-4ixr3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:key" /></template>
