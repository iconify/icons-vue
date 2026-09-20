<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy4qd-b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy4qd-b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bar-big" /></template>
