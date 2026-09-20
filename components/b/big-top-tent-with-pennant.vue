<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r401p9bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r401p9bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:big-top-tent-with-pennant" /></template>
