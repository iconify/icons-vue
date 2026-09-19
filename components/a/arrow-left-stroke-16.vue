<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7nkwz-gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x7nkwz-gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-stroke-16" /></template>
