<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqet3pb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yqet3pb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:home-modern-16-solid" /></template>
