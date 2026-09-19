<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozy7hsv8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ozy7hsv8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:floppy2" /></template>
