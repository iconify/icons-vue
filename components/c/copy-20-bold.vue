<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd5atu08j.css';
import '../../css/v/veyzdwbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cd5atu08j"/><path class="veyzdwbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:copy-20-bold" /></template>
