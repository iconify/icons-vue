<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtjs_dbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gtjs_dbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:arrow-down-left" /></template>
