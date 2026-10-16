<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijs8fxbia.css';
import '../../css/r/ro9_j1_cs.css';
import '../../css/e/eilf2ebne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ijs8fxbia"/><path class="ro9_j1_cs"/><path class="eilf2ebne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charging-canopy-20" /></template>
