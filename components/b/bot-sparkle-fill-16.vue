<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa7mqbxdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sa7mqbxdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bot-sparkle-fill-16" /></template>
