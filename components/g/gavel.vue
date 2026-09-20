<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luw2295ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="luw2295ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:gavel" /></template>
