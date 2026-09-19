<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr3c7yb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yr3c7yb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flashlight" /></template>
