<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okctgjbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="okctgjbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-120" /></template>
