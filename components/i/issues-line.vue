<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp1ebbwyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp1ebbwyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:issues-line" /></template>
