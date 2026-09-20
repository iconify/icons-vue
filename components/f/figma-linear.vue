<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gvhflea0d.css';
import '../../css/k/kq8vefznw.css';
import '../../css/p/pide31b3u.css';
import '../../css/q/qd7grabik.css';
import '../../css/h/hrnbbwbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gvhflea0d"/><path class="kq8vefznw"/><path class="pide31b3u"/><path class="qd7grabik"/><path class="hrnbbwbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:figma-linear" /></template>
