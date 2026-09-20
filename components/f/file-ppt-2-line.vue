<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz38d-r1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz38d-r1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-ppt-2-line" /></template>
