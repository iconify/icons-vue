<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p678uh31n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p678uh31n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-3-story-gabled-roof" /></template>
