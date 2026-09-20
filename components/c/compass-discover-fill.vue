<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvkad84mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvkad84mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:compass-discover-fill" /></template>
