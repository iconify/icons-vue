<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jzwkv4bnr.css';
import '../../css/i/ifj46hwma.css';
import '../../css/d/dalt38r3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jzwkv4bnr"/><path class="ifj46hwma"/><path clip-rule="evenodd" class="dalt38r3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:clipboard-check" /></template>
