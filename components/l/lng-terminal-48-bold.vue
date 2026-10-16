<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xona1pb7d.css';
import '../../css/c/cnes96yjo.css';
import '../../css/o/oe0sopmij.css';
import '../../css/b/b1vrjkb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xona1pb7d"/><path class="cnes96yjo"/><path class="oe0sopmij"/><path class="b1vrjkb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lng-terminal-48-bold" /></template>
