<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8f5z6b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r8f5z6b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:floorplan" /></template>
