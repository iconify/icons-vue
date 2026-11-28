<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ozwbchj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w7ozwbchj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ice-cubes-to-cup" /></template>
