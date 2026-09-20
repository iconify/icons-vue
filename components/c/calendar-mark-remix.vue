<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf_ncgock.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rf_ncgock"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:calendar-mark-remix" /></template>
