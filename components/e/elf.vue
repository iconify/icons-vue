<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k68cacb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k68cacb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:elf" /></template>
