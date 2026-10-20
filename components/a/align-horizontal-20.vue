<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh0r8abuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vh0r8abuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-horizontal-20" /></template>
