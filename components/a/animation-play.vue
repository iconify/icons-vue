<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuz937pqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuz937pqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:animation-play" /></template>
