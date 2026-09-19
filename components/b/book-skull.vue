<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgq1gye8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bgq1gye8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:book-skull" /></template>
