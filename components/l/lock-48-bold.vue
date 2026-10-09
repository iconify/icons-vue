<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jviohsbmh.css';
import '../../css/h/he3kxyb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jviohsbmh"/><path class="he3kxyb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-48-bold" /></template>
