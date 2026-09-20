<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zebs4qb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zebs4qb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:layers-1-16" /></template>
