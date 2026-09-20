<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj5e91bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj5e91bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-expand-vertical" /></template>
