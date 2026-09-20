<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xja25sb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xja25sb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clip" /></template>
