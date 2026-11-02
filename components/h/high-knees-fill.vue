<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7w6djb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7w6djb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:high-knees-fill" /></template>
