<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q86ldobxb.css';
import '../../css/c/cd-6u1e9y.css';
import '../../css/u/u4synlg4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q86ldobxb"/><path class="cd-6u1e9y wm-s"/><path class="u4synlg4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-branch-plus-duo" /></template>
