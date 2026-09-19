<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb1t7fbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb1t7fbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:bluesky" /></template>
