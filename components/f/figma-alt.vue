<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6uj5ccbk.css';
import '../../css/v/vod56msze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6uj5ccbk"/><path class="vod56msze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:figma-alt" /></template>
