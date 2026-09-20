<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbotdmbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbotdmbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:discussion-plus-outline" /></template>
