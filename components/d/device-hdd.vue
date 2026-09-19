<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qxbr31b0h.css';
import '../../css/h/hswojb3hz.css';
import '../../css/q/qznqlw_ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="qxbr31b0h"/><path class="hswojb3hz"/><path class="qznqlw_ir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:device-hdd" /></template>
