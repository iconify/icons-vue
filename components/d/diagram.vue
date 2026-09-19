<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3vijhb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i3vijhb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:diagram" /></template>
