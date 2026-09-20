<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rc8_piqts.css';
import '../../css/a/amtsbybzq.css';
import '../../css/o/o8bzarb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rc8_piqts"/><path class="amtsbybzq"/><path class="o8bzarb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="unjs:h3" /></template>
