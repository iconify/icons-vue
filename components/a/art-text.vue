<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtyo55uzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtyo55uzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:art-text" /></template>
