<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmrlrrbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmrlrrbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:headphone-2-line" /></template>
