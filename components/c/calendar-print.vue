<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l0odr6zsw.css';
import '../../css/d/dz_acn-zs.css';
import '../../css/f/f78tv89nt.css';
import '../../css/m/m4m9b5sui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="l0odr6zsw"/><path clip-rule="evenodd" class="dz_acn-zs"/><path clip-rule="evenodd" class="f78tv89nt"/><path class="m4m9b5sui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:calendar-print" /></template>
