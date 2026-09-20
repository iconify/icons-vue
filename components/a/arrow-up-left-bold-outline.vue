<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv2f2z9dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv2f2z9dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-left-bold-outline" /></template>
