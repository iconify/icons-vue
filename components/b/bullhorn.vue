<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6l63wbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="f6l63wbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bullhorn" /></template>
