<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt9l-fdny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9l-fdny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:analytics-line" /></template>
