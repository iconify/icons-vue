<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0pl3acvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w0pl3acvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bag-heart" /></template>
