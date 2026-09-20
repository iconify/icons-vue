<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4b11056f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4b11056f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-1-line" /></template>
