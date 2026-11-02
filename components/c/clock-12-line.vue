<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfbejcc8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfbejcc8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-12-line" /></template>
