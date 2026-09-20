<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uevab_bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uevab_bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:animation-play-outline" /></template>
