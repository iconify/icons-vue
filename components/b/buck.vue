<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iveanybiz.css';
import '../../css/p/p-qjc1xpf.css';
import '../../css/l/ljxetke2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="iveanybiz"><path class="p-qjc1xpf"/><path class="ljxetke2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:buck" /></template>
