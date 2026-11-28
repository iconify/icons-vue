<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4na7gnpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4na7gnpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:layers-x" /></template>
