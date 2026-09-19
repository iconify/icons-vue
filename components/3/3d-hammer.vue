<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n41-xbbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n41-xbbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:3d-hammer" /></template>
