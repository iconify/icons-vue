<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0srfx45m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y0srfx45m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:airport" /></template>
