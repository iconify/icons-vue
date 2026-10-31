<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnxrlvq5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nnxrlvq5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building-with-garage-door" /></template>
