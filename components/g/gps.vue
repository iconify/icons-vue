<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-0akj67l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-0akj67l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gps" /></template>
