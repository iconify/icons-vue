<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2cvh0bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2cvh0bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:current-dc" /></template>
