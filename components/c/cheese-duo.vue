<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2d3of8ot.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nl_qurb3s.css';
import '../../css/k/kf2fi9bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2d3of8ot secondary"/><g class="dt0cm9dhy primary"><path class="nl_qurb3s"/><path class="kf2fi9bdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cheese-duo" /></template>
