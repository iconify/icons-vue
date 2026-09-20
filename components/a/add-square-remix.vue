<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pln6dubev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pln6dubev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-square-remix" /></template>
