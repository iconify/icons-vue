<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pzauvpb_u.css';
import '../../css/e/eepz6tbhj.css';
import '../../css/l/lq2ydebmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="pzauvpb_u"/><path class="eepz6tbhj"/><path class="lq2ydebmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:battery-full" /></template>
