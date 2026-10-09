<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsiaoacww.css';
import '../../css/p/pe35xebhe.css';
import '../../css/u/um7q16f0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fsiaoacww"/><path class="pe35xebhe"/><path class="um7q16f0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bookmark-plus-48" /></template>
