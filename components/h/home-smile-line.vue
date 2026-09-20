<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqf0ry-2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqf0ry-2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-smile-line" /></template>
