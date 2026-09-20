<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hpomyibzb.css';
import '../../css/q/q5txpcciu.css';
import '../../css/w/wumnombuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hpomyibzb"/><path class="q5txpcciu"/><path clip-rule="evenodd" class="wumnombuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-horizontal-bold" /></template>
