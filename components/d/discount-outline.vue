<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwl3xzbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwl3xzbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:discount-outline" /></template>
