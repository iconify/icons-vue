<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8l00fqcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v8l00fqcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:increase-16" /></template>
