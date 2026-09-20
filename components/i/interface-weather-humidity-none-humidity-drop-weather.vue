<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2n_mllgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="z2n_mllgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-weather-humidity-none-humidity-drop-weather" /></template>
