<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7vy64bnv.css';
import '../../css/q/q_02szb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="SVGLuCnNb4Q" class="w7vy64bnv"/></defs><path class="q_02szb5c"/><use href="#SVGLuCnNb4Q"/><use href="#SVGLuCnNb4Q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-css-open" /></template>
