<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eexvgpkjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eexvgpkjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cannabis-off" /></template>
