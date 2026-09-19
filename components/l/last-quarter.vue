<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2fxy5pif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p2fxy5pif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:last-quarter" /></template>
