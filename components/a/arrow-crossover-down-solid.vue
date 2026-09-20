<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2_uefpzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h2_uefpzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-crossover-down-solid" /></template>
