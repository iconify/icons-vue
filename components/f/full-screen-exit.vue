<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bad0-bbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bad0-bbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:full-screen-exit" /></template>
