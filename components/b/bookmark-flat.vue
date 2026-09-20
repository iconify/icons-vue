<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0778o7nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f0778o7nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:bookmark-flat" /></template>
