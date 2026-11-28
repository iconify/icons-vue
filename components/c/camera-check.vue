<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik9fwdb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik9fwdb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:camera-check" /></template>
