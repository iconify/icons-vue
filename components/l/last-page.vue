<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1-1yjr8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1-1yjr8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:last-page" /></template>
