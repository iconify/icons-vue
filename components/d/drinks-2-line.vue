<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy7n7d1lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy7n7d1lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drinks-2-line" /></template>
