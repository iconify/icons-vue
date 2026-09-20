<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obdbvh-1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obdbvh-1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:exit" /></template>
