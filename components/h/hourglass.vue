<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb0i0kbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":432};
const content = `<path class="bb0i0kbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hourglass" /></template>
