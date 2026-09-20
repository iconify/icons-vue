<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i21681b6z.css';
import '../../css/d/d6dberbkk.css';
import '../../css/h/h8pu4qb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i21681b6z"/><path class="d6dberbkk"/><path class="h8pu4qb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-4-bold-duotone" /></template>
