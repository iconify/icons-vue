<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v70ca4k4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v70ca4k4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cable-stayed-bridge" /></template>
