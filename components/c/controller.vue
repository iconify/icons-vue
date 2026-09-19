<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/if8c-p6ab.css';
import '../../css/r/r0mx2p4-s.css';
import '../../css/g/gqfbtia_s.css';
import '../../css/j/j7whtobzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="if8c-p6ab"/><path clip-rule="evenodd" class="r0mx2p4-s"/><path class="gqfbtia_s"/><path class="j7whtobzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:controller" /></template>
