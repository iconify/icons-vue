<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a70ga4nnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a70ga4nnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:glass-whiskey" /></template>
