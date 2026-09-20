<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yez6l33me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yez6l33me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-diagonal-s-2-fill" /></template>
