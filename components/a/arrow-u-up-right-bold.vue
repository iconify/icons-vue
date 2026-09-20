<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylpowi0yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylpowi0yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-up-right-bold" /></template>
