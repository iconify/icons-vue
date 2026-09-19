<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5c-sgb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":456};
const content = `<path class="m5c-sgb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-case-play" /></template>
