<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9med6bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e9med6bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:grab-handle" /></template>
