<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9m3msb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h9m3msb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-down" /></template>
