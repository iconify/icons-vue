<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zngyyzlhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zngyyzlhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-circle-fill-16" /></template>
