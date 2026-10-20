<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcfuqov3g.css';
import '../../css/w/wb2m571ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gcfuqov3g"/><path class="wb2m571ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-sparkle-48-bold" /></template>
