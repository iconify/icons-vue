<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv-71uxns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qv-71uxns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-center-20-bold" /></template>
