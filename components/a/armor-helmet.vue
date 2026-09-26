<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5d7bg7bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x5d7bg7bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:armor-helmet" /></template>
