<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nszo3v0eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nszo3v0eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-expand" /></template>
