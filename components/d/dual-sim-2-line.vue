<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd48edbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd48edbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dual-sim-2-line" /></template>
