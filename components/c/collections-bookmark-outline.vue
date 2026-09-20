<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qudyog_ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qudyog_ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:collections-bookmark-outline" /></template>
