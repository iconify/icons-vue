<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8dnbvlph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f8dnbvlph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:browser-search" /></template>
