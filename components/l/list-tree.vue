<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/b/b42uobcxl.css';
import '../../css/z/zr6c0qbrk.css';
import '../../css/v/v_qpa3bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="b42uobcxl wm-k"/><path class="wm-a zr6c0qbrk"/><path class="v_qpa3bus wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:list-tree" /></template>
