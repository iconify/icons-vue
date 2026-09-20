<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i76hc9b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i76hc9b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-9-fill" /></template>
