<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjiluybel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjiluybel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fantasy-variant" /></template>
