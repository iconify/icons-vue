<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5ye21bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5ye21bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:add-hexagon-1" /></template>
