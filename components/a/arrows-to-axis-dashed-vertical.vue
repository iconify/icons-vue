<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhqm7bb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhqm7bb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrows-to-axis-dashed-vertical" /></template>
