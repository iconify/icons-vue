<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbcr950-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbcr950-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:image-line" /></template>
