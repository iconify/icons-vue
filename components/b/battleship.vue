<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fafjl7bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fafjl7bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battleship" /></template>
