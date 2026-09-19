<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blf-jfb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="blf-jfb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:fire" /></template>
