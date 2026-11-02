<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k71_yo_lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k71_yo_lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bedside-table-2-fill" /></template>
