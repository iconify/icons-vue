<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uty38ab5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uty38ab5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:3d-move" /></template>
