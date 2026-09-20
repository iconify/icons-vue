<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni-v-ubcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ni-v-ubcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bifold-map-with-dotted-line-to-x" /></template>
