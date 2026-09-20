<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu0r17e0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cu0r17e0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-down-small" /></template>
