<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuy7yly5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zuy7yly5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:incoming-rocket" /></template>
