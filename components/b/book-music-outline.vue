<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfi01fbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfi01fbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-music-outline" /></template>
