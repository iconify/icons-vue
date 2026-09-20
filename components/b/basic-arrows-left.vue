<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbthg9fde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jbthg9fde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-arrows-left" /></template>
