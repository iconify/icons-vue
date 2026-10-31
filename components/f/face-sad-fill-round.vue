<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydtglrbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydtglrbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-sad-fill-round" /></template>
