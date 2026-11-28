<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yudp8lbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yudp8lbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:car-lock" /></template>
