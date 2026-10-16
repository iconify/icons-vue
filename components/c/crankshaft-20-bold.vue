<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xquc5jbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xquc5jbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crankshaft-20-bold" /></template>
