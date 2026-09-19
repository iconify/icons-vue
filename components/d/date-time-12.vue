<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2sb3hbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v2sb3hbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:date-time-12" /></template>
