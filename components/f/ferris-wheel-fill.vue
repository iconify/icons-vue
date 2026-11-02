<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut_z27wac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut_z27wac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ferris-wheel-fill" /></template>
