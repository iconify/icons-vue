<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjjeidcdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjjeidcdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clockwise-line" /></template>
