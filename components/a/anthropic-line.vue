<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycybfzv0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycybfzv0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:anthropic-line" /></template>
