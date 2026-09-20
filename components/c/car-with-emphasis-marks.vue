<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6h785nef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h6h785nef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-with-emphasis-marks" /></template>
