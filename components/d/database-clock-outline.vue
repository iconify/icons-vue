<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2on09xws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2on09xws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-clock-outline" /></template>
