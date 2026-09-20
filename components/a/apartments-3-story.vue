<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srlzd6bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="srlzd6bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-3-story" /></template>
