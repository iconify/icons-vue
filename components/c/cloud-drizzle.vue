<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dma4yhbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dma4yhbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-drizzle" /></template>
