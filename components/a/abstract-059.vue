<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnbm68e6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gnbm68e6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-059" /></template>
