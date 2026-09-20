<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oycylo9nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oycylo9nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cane-alt-remix" /></template>
