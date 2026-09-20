<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbcc51ung.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbcc51ung"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-left-box" /></template>
