<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wty0pzinu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wty0pzinu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cigar" /></template>
