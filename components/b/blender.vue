<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-0snhbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-0snhbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blender" /></template>
