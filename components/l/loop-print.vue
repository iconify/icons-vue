<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w09lmnx4l.css';
import '../../css/e/eicihhp-u.css';
import '../../css/s/s2w7n_bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w09lmnx4l"/><path clip-rule="evenodd" class="eicihhp-u"/><path class="s2w7n_bit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:loop-print" /></template>
