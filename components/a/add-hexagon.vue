<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqn9esczx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqn9esczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:add-hexagon" /></template>
