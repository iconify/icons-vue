<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6hv0acym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6hv0acym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-down-line" /></template>
