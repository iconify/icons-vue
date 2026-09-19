<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll8x3e97m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ll8x3e97m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kenku-head" /></template>
