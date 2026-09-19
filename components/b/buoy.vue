<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8yxl-b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8yxl-b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:buoy" /></template>
