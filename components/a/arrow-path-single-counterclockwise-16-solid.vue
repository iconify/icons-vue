<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ocxknif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l9ocxknif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-counterclockwise-16-solid" /></template>
