<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihj0scc-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ihj0scc-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:kansas-with-capital-star" /></template>
