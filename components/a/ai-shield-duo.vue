<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyj2t-l6e.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l5amd1two.css';
import '../../css/c/c9u2s_lcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyj2t-l6e secondary"/><g class="dt0cm9dhy primary"><path class="l5amd1two"/><path class="c9u2s_lcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-shield-duo" /></template>
