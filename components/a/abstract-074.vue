<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkozmf4nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rkozmf4nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-074" /></template>
