<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugm2z76fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugm2z76fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:duble-corner-arrow-4" /></template>
