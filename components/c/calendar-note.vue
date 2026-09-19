<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz8jz3rbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="rz8jz3rbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:calendar-note" /></template>
