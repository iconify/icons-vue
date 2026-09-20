<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awjitp7ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="awjitp7ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:line-arrow-rotate-right-circle-remix" /></template>
