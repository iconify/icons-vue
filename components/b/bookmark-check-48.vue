<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsiaoacww.css';
import '../../css/q/q5pax_b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fsiaoacww"/><path class="q5pax_b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bookmark-check-48" /></template>
