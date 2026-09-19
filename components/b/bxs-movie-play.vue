<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzi44cbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzi44cbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-movie-play" /></template>
