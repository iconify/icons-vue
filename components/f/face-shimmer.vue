<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq07mm04a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq07mm04a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:face-shimmer" /></template>
