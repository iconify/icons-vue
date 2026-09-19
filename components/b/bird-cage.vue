<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/corv2ebzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="corv2ebzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bird-cage" /></template>
