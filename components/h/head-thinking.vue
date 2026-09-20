<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk4y2vb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk4y2vb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-thinking" /></template>
