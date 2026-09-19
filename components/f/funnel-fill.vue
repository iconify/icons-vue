<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkzgt2baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkzgt2baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:funnel-fill" /></template>
