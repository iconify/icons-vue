<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umpeo9btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umpeo9btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-z-circle-outline" /></template>
