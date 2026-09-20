<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhzi09bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xhzi09bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-5-story" /></template>
