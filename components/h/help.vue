<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksohs1bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ksohs1bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:help" /></template>
