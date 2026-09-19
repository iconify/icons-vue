<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufie9ebgy.css';
import '../../css/z/zep2h7-hf.css';
import '../../css/h/hbs97qgzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ufie9ebgy"><path class="zep2h7-hf"/><path clip-rule="evenodd" class="hbs97qgzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:frame-select" /></template>
