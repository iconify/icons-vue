<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di0yiybee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="di0yiybee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:circles-seven" /></template>
