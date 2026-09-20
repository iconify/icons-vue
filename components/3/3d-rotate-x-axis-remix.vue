<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2wy2ubck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2wy2ubck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:3d-rotate-x-axis-remix" /></template>
