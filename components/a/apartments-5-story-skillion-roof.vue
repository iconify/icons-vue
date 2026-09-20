<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltq07achs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ltq07achs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-5-story-skillion-roof" /></template>
