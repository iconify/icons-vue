<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyolhkbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyolhkbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-clock-fill" /></template>
