<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6fwrqe6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g6fwrqe6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:calendar-week" /></template>
