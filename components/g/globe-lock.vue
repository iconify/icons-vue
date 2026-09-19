<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7xg__z-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="c7xg__z-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:globe-lock" /></template>
