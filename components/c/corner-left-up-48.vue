<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-r-yzbxr.css';
import '../../css/u/u4q8h8_yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s-r-yzbxr"/><path class="u4q8h8_yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-left-up-48" /></template>
