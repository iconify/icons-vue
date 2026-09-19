<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukp6v6bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ukp6v6bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chevron-down" /></template>
