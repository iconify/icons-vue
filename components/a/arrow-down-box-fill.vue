<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syavd4j4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syavd4j4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-box-fill" /></template>
