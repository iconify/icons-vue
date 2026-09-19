<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtgd7zbyl.css';
import '../../css/w/ws3ki_htx.css';
import '../../css/m/m3p5ncbjq.css';
import '../../css/p/pphcryv5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qtgd7zbyl"/><path class="ws3ki_htx"/><path class="m3p5ncbjq"/><path class="pphcryv5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:library-add" /></template>
