<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8tufhvwy.css';
import '../../css/y/y8-ea6dak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8tufhvwy"/><path class="y8-ea6dak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-rtl-fill-16" /></template>
