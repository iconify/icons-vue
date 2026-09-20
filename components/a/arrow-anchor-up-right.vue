<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbd_-abaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lbd_-abaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:arrow-anchor-up-right" /></template>
