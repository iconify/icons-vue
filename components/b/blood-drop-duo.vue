<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_rs8f8d.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s0rwsfbqk.css';
import '../../css/t/tsrrv4k8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary v3_rs8f8d"/><g class="dt0cm9dhy primary"><path class="s0rwsfbqk"/><path class="tsrrv4k8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:blood-drop-duo" /></template>
