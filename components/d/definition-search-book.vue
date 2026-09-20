<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvpm8dayr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xvpm8dayr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:definition-search-book" /></template>
