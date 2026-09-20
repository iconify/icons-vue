<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fen0n320y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fen0n320y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cup-off-outline" /></template>
