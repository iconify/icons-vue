<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcnm0i4-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jcnm0i4-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bench-with-shelter" /></template>
