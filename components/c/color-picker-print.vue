<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gag497ble.css';
import '../../css/e/e0fv-pquy.css';
import '../../css/y/yt-6yebqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="gag497ble"/><path clip-rule="evenodd" class="e0fv-pquy"/><path class="yt-6yebqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:color-picker-print" /></template>
