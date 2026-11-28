<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v8w075vzh.css';
import '../../css/i/i8vw3obrx.css';
import '../../css/f/febcbpb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="v8w075vzh"/><path class="i8vw3obrx"/><path class="febcbpb6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-input" /></template>
