<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo82r35gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo82r35gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-heart-line" /></template>
