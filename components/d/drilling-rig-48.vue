<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf4atacsq.css';
import '../../css/a/anx3tw60h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sf4atacsq"/><path class="anx3tw60h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drilling-rig-48" /></template>
