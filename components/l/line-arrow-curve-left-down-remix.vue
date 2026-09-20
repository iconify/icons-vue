<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vre4ikblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vre4ikblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-curve-left-down-remix" /></template>
