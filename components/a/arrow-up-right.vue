<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5o5j3omz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s5o5j3omz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:arrow-up-right" /></template>
