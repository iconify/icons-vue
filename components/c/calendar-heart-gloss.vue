<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5zqsvn8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5zqsvn8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-heart-gloss" /></template>
