<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfqcq4bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dfqcq4bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-fog" /></template>
