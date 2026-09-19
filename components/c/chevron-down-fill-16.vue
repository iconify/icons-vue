<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm1l5ccia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xm1l5ccia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-down-fill-16" /></template>
