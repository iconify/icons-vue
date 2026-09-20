<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dc43t0b2s.css';
import '../../css/p/pgvt321cd.css';
import '../../css/d/dwptqjbme.css';
import '../../css/c/c_z_abcdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dc43t0b2s"/><path class="pgvt321cd"/><path class="dwptqjbme"/><path clip-rule="evenodd" class="c_z_abcdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-square-outline" /></template>
