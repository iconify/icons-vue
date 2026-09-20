<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcpm6yshk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gcpm6yshk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dashboard-3-remix" /></template>
