<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t70mwlbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t70mwlbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:frog" /></template>
