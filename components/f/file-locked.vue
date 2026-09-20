<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b_9rv5rhc.css';
import '../../css/w/w4w65tb6p.css';
import '../../css/n/nee9bt-sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b_9rv5rhc"/><path class="w4w65tb6p"/><path class="nee9bt-sy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-locked" /></template>
