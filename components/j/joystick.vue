<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px6o2gbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="px6o2gbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:joystick" /></template>
