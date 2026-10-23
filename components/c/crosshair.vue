<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d885-7b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d885-7b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:crosshair" /></template>
