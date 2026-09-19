<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar79qkbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ar79qkbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:calendar-day" /></template>
