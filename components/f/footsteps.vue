<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr_t6obzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mr_t6obzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:footsteps" /></template>
