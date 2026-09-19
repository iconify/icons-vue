<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6wljthwv.css';
import '../../css/b/bhxknwbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6wljthwv"/><path class="bhxknwbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:chuck" /></template>
