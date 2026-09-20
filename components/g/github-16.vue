<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q94xyqb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q94xyqb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:github-16" /></template>
