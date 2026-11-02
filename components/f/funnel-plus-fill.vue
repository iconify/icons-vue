<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rve_w0bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rve_w0bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:funnel-plus-fill" /></template>
