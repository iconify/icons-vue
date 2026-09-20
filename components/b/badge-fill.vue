<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzdnue6lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzdnue6lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-fill" /></template>
