<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7y--t7eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a7y--t7eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:area-chart-filled" /></template>
