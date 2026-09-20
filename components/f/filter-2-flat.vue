<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei0prijnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ei0prijnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:filter-2-flat" /></template>
