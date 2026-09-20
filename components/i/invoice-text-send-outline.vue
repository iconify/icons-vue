<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uojy9gomk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uojy9gomk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-send-outline" /></template>
