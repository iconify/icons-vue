<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgw8ko-wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgw8ko-wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:egg-defense" /></template>
