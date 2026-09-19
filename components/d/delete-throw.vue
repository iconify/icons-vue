<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j-4vkdb5j.css';
import '../../css/f/fhnp4c6xr.css';
import '../../css/e/eojnwibxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j-4vkdb5j"/><path class="fhnp4c6xr"/><path class="eojnwibxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-throw" /></template>
