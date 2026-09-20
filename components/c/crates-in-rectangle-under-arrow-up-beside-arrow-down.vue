<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkvud5qcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lkvud5qcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crates-in-rectangle-under-arrow-up-beside-arrow-down" /></template>
