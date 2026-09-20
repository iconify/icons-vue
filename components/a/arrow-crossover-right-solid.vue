<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfrm27b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dfrm27b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-crossover-right-solid" /></template>
