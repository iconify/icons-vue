<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7ybh6b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7ybh6b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comments-text-outline" /></template>
