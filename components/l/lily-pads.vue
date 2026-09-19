<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ipcjk3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5ipcjk3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lily-pads" /></template>
