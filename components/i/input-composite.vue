<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d01hhabgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="d01hhabgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:input-composite" /></template>
