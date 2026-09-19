<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8_ww-5zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8_ww-5zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gloop" /></template>
