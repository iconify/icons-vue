<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqevs9bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqevs9bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-arrow-up" /></template>
