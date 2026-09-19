<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o79otvbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o79otvbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-015" /></template>
