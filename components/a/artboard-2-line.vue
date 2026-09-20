<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6che1bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6che1bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:artboard-2-line" /></template>
