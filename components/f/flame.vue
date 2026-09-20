<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry9lquaxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry9lquaxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:flame" /></template>
