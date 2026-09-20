<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3jhhxjvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m3jhhxjvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:i-in-square" /></template>
