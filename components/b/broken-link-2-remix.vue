<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uke6mih8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uke6mih8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:broken-link-2-remix" /></template>
