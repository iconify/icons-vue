<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae2-w0cbe.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/y8d9j006r.css';
import '../../css/p/pr0b1fbfw.css';
import '../../css/j/jbc4vb_8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae2-w0cbe secondary"/><g class="dt0cm9dhy primary"><path class="y8d9j006r"/><path class="pr0b1fbfw"/><path class="jbc4vb_8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-face-look-up-duo" /></template>
