<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc7w7oqjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vc7w7oqjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:index-flush" /></template>
