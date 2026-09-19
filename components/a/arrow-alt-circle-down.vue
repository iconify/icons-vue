<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9rh5p0qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j9rh5p0qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-alt-circle-down" /></template>
