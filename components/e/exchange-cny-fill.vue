<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h36zf1bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h36zf1bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:exchange-cny-fill" /></template>
