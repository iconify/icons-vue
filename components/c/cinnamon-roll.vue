<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pxy5wxb2o.css';
import '../../css/h/h2tkw0b0p.css';
import '../../css/k/kqlaetbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pxy5wxb2o"/><path class="h2tkw0b0p"/><path class="kqlaetbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cinnamon-roll" /></template>
