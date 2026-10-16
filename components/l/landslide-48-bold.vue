<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc_i6bbxk.css';
import '../../css/f/fw2t25bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hc_i6bbxk"/><path class="fw2t25bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landslide-48-bold" /></template>
