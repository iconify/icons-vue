<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vioo8qbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vioo8qbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-cycle-stroke-16" /></template>
