<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsuf0h8wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bsuf0h8wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:energy-tank" /></template>
