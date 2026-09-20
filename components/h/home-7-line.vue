<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/livxeibzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="livxeibzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-7-line" /></template>
