<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9o1tloua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l9o1tloua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:aperture" /></template>
