<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtfaehbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtfaehbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-check-2-line" /></template>
