<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1n5p1ycg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u1n5p1ycg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bars-3-bottom-center-16-solid" /></template>
