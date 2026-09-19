<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/p/pqia5ybpf.css';
import '../../css/y/yg91g4wbg.css';
import '../../css/t/tmt74cc5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><ellipse transform="matrix(-1 0 0 1 20 2)" class="pqia5ybpf"/><path class="yg91g4wbg"/><path class="tmt74cc5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:coin" /></template>
