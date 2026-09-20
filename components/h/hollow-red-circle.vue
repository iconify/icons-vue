<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbepz408x.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/q/qyj032rbb.css';
import '../../css/b/byn-yqbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kbepz408x"/><g class="jn8qy4bru"><circle class="qyj032rbb"/><circle class="byn-yqbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hollow-red-circle" /></template>
