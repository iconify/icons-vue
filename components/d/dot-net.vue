<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1fz6zbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1fz6zbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dot-net" /></template>
