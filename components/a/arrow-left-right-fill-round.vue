<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_tz6bhzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_tz6bhzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-right-fill-round" /></template>
