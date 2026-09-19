<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo6ekxl-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="uo6ekxl-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:caret-up" /></template>
