<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra9atrb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ra9atrb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-bmp" /></template>
