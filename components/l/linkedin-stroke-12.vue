<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcemllbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lcemllbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:linkedin-stroke-12" /></template>
