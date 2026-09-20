<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp7d0ubjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp7d0ubjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cookie-man-line" /></template>
