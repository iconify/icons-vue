<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se-3hvqef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se-3hvqef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-location-outline" /></template>
