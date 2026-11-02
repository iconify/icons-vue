<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4bg2m00a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4bg2m00a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bold-line" /></template>
