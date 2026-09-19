<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2d7j5b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m2d7j5b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:easel2" /></template>
