<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txxypwbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txxypwbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-big-up-dash-fill" /></template>
