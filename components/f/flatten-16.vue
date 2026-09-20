<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zys39uvkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zys39uvkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:flatten-16" /></template>
