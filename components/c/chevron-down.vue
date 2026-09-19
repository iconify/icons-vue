<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6qxpw2du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y6qxpw2du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chevron-down" /></template>
