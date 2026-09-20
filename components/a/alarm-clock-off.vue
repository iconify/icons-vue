<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytx9e-bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytx9e-bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:alarm-clock-off" /></template>
