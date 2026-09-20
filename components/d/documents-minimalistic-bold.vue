<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/od6evsbxr.css';
import '../../css/s/s-ho2qb0i.css';
import '../../css/e/e_2bay6_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="od6evsbxr"/><path class="s-ho2qb0i"/><path class="e_2bay6_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:documents-minimalistic-bold" /></template>
