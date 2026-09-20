<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mroolm-ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mroolm-ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:filter-2-remix" /></template>
