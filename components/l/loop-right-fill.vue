<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-6h55buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-6h55buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loop-right-fill" /></template>
