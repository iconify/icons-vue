<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlhx3cbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dlhx3cbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:line-arrow-expand-window-2-remix" /></template>
