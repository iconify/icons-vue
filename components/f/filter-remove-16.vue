<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn4sofbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hn4sofbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:filter-remove-16" /></template>
