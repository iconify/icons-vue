<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl8rzyvoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl8rzyvoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:golf-cart" /></template>
