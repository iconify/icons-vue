<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9wfist3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<path class="s9wfist3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:linegraph" /></template>
