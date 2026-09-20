<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnwa2-bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnwa2-bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-l-box" /></template>
