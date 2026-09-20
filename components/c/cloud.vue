<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i6ken2b7v.css';
import '../../css/a/agal0ib3d.css';
import '../../css/p/pymdlybof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6ken2b7v"/><path class="agal0ib3d"/><path class="pymdlybof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber-color:cloud" /></template>
