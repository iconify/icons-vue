<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4bkgwbdg.css';
import '../../css/d/d0q_czbpk.css';
import '../../css/k/kgli6xbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4bkgwbdg"/><path class="d0q_czbpk"/><path class="kgli6xbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geothermal-plant-alert-48-bold" /></template>
