<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrmfh6b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jrmfh6b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-left-fill-16" /></template>
