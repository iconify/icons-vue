<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9q1o1tfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9q1o1tfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:low-temperature-fill" /></template>
