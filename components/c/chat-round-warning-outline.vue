<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mlb6dabuy.css';
import '../../css/m/m_ledbb3w.css';
import '../../css/m/m_goimbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mlb6dabuy"/><path class="m_ledbb3w"/><path clip-rule="evenodd" class="m_goimbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-warning-outline" /></template>
