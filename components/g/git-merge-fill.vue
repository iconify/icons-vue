<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygpegbo2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygpegbo2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-merge-fill" /></template>
