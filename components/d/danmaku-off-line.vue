<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2a1s-e8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2a1s-e8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:danmaku-off-line" /></template>
