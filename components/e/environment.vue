<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0en27b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e0en27b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:environment" /></template>
