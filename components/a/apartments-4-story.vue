<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkvyqmbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gkvyqmbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-4-story" /></template>
