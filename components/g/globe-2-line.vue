<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltb8g75pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltb8g75pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-2-line" /></template>
