<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2hg3_40q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u2hg3_40q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-right-20" /></template>
