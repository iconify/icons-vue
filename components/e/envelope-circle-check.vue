<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4neldb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="t4neldb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:envelope-circle-check" /></template>
