<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce0984b4t.css';
import '../../css/t/tetsfk0bz.css';
import '../../css/w/wl07m1b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ce0984b4t"/><path class="tetsfk0bz"/><path class="wl07m1b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydraulic-press-48" /></template>
