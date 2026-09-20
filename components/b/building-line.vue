<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4kkvvgyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4kkvvgyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:building-line" /></template>
