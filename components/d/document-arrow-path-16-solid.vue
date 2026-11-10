<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_dvcp49q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r_dvcp49q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:document-arrow-path-16-solid" /></template>
