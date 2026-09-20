<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdy-st72z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdy-st72z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-2-line" /></template>
