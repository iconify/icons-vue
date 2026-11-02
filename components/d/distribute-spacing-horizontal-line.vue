<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb75kfcpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb75kfcpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:distribute-spacing-horizontal-line" /></template>
