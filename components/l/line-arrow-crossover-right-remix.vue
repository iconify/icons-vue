<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_vulybfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w_vulybfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-crossover-right-remix" /></template>
