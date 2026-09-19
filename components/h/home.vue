<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1cokcivi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="z1cokcivi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:home" /></template>
