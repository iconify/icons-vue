<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjzv1qksk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjzv1qksk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-camera-off-fill" /></template>
