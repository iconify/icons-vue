<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0_7yv43z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0_7yv43z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-2-fill" /></template>
