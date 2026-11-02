<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_h_jpbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_h_jpbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-column-increasing-line" /></template>
