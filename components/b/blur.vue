<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/ftr8m-ovk.css';
import '../../css/q/q4xt-6b4w.css';
import '../../css/p/pn65m_b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ftr8m-ovk"/><path clip-rule="evenodd" class="q4xt-6b4w"/><path class="pn65m_b8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:blur" /></template>
