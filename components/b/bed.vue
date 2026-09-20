<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg16p0b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dg16p0b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bed" /></template>
