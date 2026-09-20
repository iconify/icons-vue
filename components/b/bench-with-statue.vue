<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq-tlin1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aq-tlin1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bench-with-statue" /></template>
