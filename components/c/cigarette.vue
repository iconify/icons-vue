<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0u1r3r5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0u1r3r5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cigarette" /></template>
