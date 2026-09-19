<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7_iombxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p7_iombxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:click" /></template>
