<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vr-8j8bin.css';
import '../../css/c/ce-slac7d.css';
import '../../css/l/l7jhf3bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vr-8j8bin"/><path class="ce-slac7d"/><path class="l7jhf3bei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-branch-duo" /></template>
