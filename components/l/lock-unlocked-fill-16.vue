<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd64d3bvp.css';
import '../../css/b/blynalbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fd64d3bvp"/><rect class="blynalbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lock-unlocked-fill-16" /></template>
