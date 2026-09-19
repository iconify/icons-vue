<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrolc2zcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nrolc2zcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-046" /></template>
