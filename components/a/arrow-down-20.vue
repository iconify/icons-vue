<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfzmnvd-w.css';
import '../../css/y/yo9tbkbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lfzmnvd-w"/><path class="yo9tbkbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-20" /></template>
