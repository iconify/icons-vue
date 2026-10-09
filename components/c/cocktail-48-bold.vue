<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0z0h0l9r.css';
import '../../css/n/n3dvw-bko.css';
import '../../css/t/tuurkcb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f0z0h0l9r"/><path class="n3dvw-bko"/><path class="tuurkcb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cocktail-48-bold" /></template>
