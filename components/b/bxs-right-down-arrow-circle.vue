<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8075rspi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8075rspi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-right-down-arrow-circle" /></template>
