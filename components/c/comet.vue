<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpg5sf9ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dpg5sf9ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:comet" /></template>
