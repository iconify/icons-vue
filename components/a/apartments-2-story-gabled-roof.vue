<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3qpvprfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y3qpvprfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-2-story-gabled-roof" /></template>
