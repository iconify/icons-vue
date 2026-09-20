<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et-6wtyiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et-6wtyiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-search-fill" /></template>
