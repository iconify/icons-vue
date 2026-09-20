<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjvottbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gjvottbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:graph-dot-remix" /></template>
