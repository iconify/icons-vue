<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_z3u7nyx.css';
import '../../css/w/whtgogiyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_z3u7nyx"/><path class="whtgogiyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:brackets-outline" /></template>
