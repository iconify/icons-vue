<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h070l8jto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h070l8jto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:lady" /></template>
