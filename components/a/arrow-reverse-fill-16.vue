<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq3d8hulp.css';
import '../../css/i/izk0irbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eq3d8hulp"/><path class="izk0irbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-reverse-fill-16" /></template>
