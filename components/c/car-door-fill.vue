<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k37aljltl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k37aljltl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-door-fill" /></template>
