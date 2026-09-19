<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm0ys2uoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm0ys2uoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-down" /></template>
