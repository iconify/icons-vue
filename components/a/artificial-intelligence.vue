<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgvzodboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgvzodboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:artificial-intelligence" /></template>
