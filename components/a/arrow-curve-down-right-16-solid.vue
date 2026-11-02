<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u73kj-bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u73kj-bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-down-right-16-solid" /></template>
