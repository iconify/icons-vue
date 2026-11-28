<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfdi_2b9g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tzyrenbep.css';
import '../../css/e/e4rg5h2em.css';
import '../../css/y/yiyni5b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfdi_2b9g secondary"/><g class="dt0cm9dhy primary"><path class="tzyrenbep"/><path class="e4rg5h2em"/><path class="yiyni5b1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lightbulb-duo" /></template>
