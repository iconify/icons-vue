<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy7lazj2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy7lazj2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-off-line" /></template>
