<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdwi5bclm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdwi5bclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:browser-line" /></template>
