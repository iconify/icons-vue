<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jj9dgh_2r.css';
import '../../css/t/t4f9bbbal.css';
import '../../css/p/p87szkrwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jj9dgh_2r"/><path class="t4f9bbbal"/><path clip-rule="evenodd" class="p87szkrwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-money-duotone" /></template>
