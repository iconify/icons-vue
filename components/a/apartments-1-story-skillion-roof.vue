<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcnmdn8pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lcnmdn8pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-1-story-skillion-roof" /></template>
