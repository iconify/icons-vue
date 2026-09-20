<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwe-d0bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwe-d0bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:balloon" /></template>
