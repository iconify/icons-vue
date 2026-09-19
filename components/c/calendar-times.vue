<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzjwhcbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wzjwhcbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:calendar-times" /></template>
