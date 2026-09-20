<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd4yb3bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd4yb3bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-select" /></template>
