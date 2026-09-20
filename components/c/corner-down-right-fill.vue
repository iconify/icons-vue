<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se3cadkfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se3cadkfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-down-right-fill" /></template>
