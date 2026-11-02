<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6gis4zqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6gis4zqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:donut-fill" /></template>
