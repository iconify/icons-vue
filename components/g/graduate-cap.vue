<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_hw5drjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d_hw5drjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:graduate-cap" /></template>
