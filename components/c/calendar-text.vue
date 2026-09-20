<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d93uw7bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d93uw7bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-text" /></template>
