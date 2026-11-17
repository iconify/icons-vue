<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0xr0hjbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0xr0hjbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrows-from-axis-dashed-horizontal" /></template>
