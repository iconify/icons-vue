<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy68n8jis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hy68n8jis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forklift-48" /></template>
