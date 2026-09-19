<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqytkfb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tqytkfb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:imp" /></template>
