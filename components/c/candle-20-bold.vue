<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoazbdbsd.css';
import '../../css/r/rzmdligbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uoazbdbsd"/><path class="rzmdligbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:candle-20-bold" /></template>
