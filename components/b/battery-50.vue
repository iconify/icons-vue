<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onw2bx3kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="onw2bx3kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battery-50" /></template>
