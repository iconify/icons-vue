<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt7sh2lev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt7sh2lev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-charging-line" /></template>
