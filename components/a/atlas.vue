<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vscks4bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vscks4bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:atlas" /></template>
