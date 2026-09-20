<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6h4-2b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h6h4-2b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:full-battery" /></template>
