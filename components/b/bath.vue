<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsom4l03p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsom4l03p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bath" /></template>
