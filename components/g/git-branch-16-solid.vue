<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnfy8db-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nnfy8db-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:git-branch-16-solid" /></template>
