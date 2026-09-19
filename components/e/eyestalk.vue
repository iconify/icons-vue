<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl26o3b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tl26o3b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eyestalk" /></template>
