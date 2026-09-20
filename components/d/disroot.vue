<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy7uecbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy7uecbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:disroot" /></template>
