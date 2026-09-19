<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r54u05boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r54u05boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:house-circle-check" /></template>
