<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flgyrexts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="flgyrexts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:branch" /></template>
