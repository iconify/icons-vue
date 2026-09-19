<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtm7_qb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtm7_qb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-016" /></template>
