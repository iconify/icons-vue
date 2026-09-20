<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1iosjpsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z1iosjpsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flagstick-with-flag-in-hole" /></template>
