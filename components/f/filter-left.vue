<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuivb7bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fuivb7bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filter-left" /></template>
