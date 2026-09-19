<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a0nds4_gn.css';
import '../../css/y/yovjmyyvz.css';
import '../../css/u/u8qw3jobp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="a0nds4_gn"/><path clip-rule="evenodd" class="yovjmyyvz"/><path class="u8qw3jobp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:loop-minus-print" /></template>
