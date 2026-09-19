<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9rc97b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9rc97b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:calendar-edit" /></template>
