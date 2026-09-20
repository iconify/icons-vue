<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1vx7j78p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1vx7j78p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-tags" /></template>
