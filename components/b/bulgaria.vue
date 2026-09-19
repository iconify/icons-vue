<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou4zimbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ou4zimbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bulgaria" /></template>
