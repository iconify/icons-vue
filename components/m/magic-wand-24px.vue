<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v7_wzybpw.css';
import '../../css/w/wl8v1bcuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v7_wzybpw"/><path clip-rule="evenodd" class="wl8v1bcuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:magic-wand-24px" /></template>
