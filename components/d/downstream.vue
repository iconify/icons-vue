<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2iwfpb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h2iwfpb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:downstream" /></template>
