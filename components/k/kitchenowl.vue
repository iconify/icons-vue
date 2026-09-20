<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf24crklk.css';
import '../../css/y/yr2jp-bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bf24crklk"/><path class="yr2jp-bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kitchenowl" /></template>
