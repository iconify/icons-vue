<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu4to9b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cu4to9b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:duble-corner-arrow-blod-2" /></template>
