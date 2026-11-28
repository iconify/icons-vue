<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1n8e7bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1n8e7bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:disco-ball" /></template>
