<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s23avd-hl.css';
import '../../css/l/l8dg_3bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s23avd-hl"/><path class="l8dg_3bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clapperboard-48" /></template>
