<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjuv8i3nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjuv8i3nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-1-light" /></template>
