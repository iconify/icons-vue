<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysn8ry8zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ysn8ry8zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ai-edit-robot-solid" /></template>
