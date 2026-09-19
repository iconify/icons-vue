<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rat-wm04r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rat-wm04r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:detonator" /></template>
