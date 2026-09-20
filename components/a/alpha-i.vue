<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l180r0tap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l180r0tap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-i" /></template>
