<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m25665yni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m25665yni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ham-shank" /></template>
