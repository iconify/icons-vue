<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em2davzvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="em2davzvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-list-stroke-16" /></template>
