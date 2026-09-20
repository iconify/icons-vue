<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i84w1hbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i84w1hbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:feature-flag-disabled" /></template>
