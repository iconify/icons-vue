<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unz_1ke_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unz_1ke_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cubeforce" /></template>
