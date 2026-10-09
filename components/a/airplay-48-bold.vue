<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psdyb3bve.css';
import '../../css/n/neg1e0pbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="psdyb3bve"/><path class="neg1e0pbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airplay-48-bold" /></template>
