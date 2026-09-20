<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg-6e0eht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg-6e0eht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-box" /></template>
