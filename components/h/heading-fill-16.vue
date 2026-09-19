<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of__cjgqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="of__cjgqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heading-fill-16" /></template>
