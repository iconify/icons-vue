<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5am15b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u5am15b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:globe-europe-africa" /></template>
