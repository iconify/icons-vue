<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3lw51fjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o3lw51fjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:arrow-circle-up" /></template>
