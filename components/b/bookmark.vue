<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un-a6pokw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="un-a6pokw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bookmark" /></template>
