<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw9-8sbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw9-8sbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:flash-outline" /></template>
