<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv7jw7b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv7jw7b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-radius-line" /></template>
