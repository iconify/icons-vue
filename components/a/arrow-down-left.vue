<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqa9nybtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jqa9nybtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-down-left" /></template>
