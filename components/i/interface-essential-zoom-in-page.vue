<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm9jpqbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mm9jpqbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-zoom-in-page" /></template>
