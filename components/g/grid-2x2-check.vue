<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfbvi1bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfbvi1bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grid-2x2-check" /></template>
