<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftft7buul.css';
import '../../css/o/oanow-b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ftft7buul"/><path class="oanow-b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bed-48" /></template>
