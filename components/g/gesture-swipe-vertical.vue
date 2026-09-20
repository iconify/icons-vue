<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymqtzmvzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymqtzmvzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-swipe-vertical" /></template>
