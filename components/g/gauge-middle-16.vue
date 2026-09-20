<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9lwlibmh.css';
import '../../css/m/mocmm6bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r9lwlibmh"/><path class="mocmm6bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gauge-middle-16" /></template>
