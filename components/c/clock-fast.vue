<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q127-w8jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q127-w8jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-fast" /></template>
