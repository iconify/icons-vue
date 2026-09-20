<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffajtebrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffajtebrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-apple-outline" /></template>
