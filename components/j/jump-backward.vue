<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/c/chegubbiq.css';
import '../../css/y/ybum0287x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="chegubbiq"/><path class="ybum0287x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:jump-backward" /></template>
