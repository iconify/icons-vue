<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al27dqmyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="al27dqmyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:flag-solid" /></template>
