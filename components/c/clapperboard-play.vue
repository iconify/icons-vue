<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvx2kubbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvx2kubbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-play" /></template>
