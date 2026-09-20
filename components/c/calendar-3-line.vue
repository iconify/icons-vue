<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anv1cbbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anv1cbbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-3-line" /></template>
