<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3-znrybr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3-znrybr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-line" /></template>
