<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0aiwjbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0aiwjbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:browser-firefox" /></template>
