<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_9-ozbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t_9-ozbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:fork-alt" /></template>
