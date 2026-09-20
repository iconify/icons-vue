<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q19o077cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q19o077cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:heart-3-line" /></template>
