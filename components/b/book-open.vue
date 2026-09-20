<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs7hcyplm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fs7hcyplm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:book-open" /></template>
