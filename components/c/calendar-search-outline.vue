<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uspsjv9tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uspsjv9tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-search-outline" /></template>
