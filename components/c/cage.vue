<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0iw-qbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r0iw-qbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:cage" /></template>
