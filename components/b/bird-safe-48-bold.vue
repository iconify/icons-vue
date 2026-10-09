<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrsls2auw.css';
import '../../css/f/fapgrnb1n.css';
import '../../css/l/l9gndm50e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nrsls2auw"/><path class="fapgrnb1n"/><path class="l9gndm50e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bird-safe-48-bold" /></template>
