<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvt79nbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yvt79nbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dome-with-crescent-moon-and-star-and-planet" /></template>
