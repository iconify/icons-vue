<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4s0-2zmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4s0-2zmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:government-line" /></template>
