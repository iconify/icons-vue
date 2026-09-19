<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt19e0-cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mt19e0-cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-gif" /></template>
