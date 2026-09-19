<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z19o4abgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z19o4abgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-pressure-monitor" /></template>
