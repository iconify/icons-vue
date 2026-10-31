<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrgryxb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrgryxb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-minus-corner-fill-round" /></template>
