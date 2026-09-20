<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1y2ibvrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1y2ibvrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bubble-filled" /></template>
