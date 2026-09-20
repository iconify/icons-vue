<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqhriccfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eqhriccfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:clockwise" /></template>
