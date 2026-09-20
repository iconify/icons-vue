<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqlsmwbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tqlsmwbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dog-1-remix" /></template>
