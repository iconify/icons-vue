<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/v90gbqbox.css';
import '../../css/c/c7voef_mm.css';
import '../../css/i/i7-tpfahw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="v90gbqbox"/><path class="c7voef_mm"/><path class="i7-tpfahw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ferris-wheel" /></template>
