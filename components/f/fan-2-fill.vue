<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv4shs_gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv4shs_gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-2-fill" /></template>
