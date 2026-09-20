<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlf2raced.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xlf2raced"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hierarchy-2" /></template>
