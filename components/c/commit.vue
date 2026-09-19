<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obyh4cyrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="obyh4cyrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:commit" /></template>
