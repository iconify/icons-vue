<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-tok76br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r-tok76br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-arrow-up-fill" /></template>
