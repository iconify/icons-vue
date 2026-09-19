<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp4b02vui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gp4b02vui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-012" /></template>
