<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5xh51bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5xh51bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-clock-fill" /></template>
