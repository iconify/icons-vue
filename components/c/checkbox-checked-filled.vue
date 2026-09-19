<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnyx6qb8j.css';
import '../../css/u/u3nzwyrar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dnyx6qb8j"/><path class="u3nzwyrar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkbox-checked-filled" /></template>
