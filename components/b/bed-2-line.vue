<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi3xz7l2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi3xz7l2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bed-2-line" /></template>
