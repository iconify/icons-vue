<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cadtdzbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cadtdzbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-10-hearts" /></template>
