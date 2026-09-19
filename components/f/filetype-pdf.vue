<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otla8nb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="otla8nb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-pdf" /></template>
