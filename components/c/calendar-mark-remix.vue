<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy4aujbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zy4aujbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calendar-mark-remix" /></template>
