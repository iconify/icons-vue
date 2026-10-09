<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3i5l3b6q.css';
import '../../css/v/v8kul2btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j3i5l3b6q"/><path class="v8kul2btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-20" /></template>
