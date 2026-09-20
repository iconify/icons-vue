<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3i_ah4rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m3i_ah4rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-synchronize-warning-remix" /></template>
