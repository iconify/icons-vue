<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f41cmzbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f41cmzbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-css" /></template>
