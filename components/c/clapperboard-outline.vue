<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4y2ht2do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4y2ht2do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-outline" /></template>
