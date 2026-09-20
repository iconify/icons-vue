<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm3x06xxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm3x06xxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hololens" /></template>
