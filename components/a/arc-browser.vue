<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt7cz-bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt7cz-bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:arc-browser" /></template>
