<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag76r2btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag76r2btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-fold" /></template>
