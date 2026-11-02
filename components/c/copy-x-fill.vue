<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd3iebcqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd3iebcqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-x-fill" /></template>
