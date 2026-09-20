<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk8q9c5sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk8q9c5sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:headphones" /></template>
