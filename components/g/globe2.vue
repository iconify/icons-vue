<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbpxv2b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qbpxv2b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:globe2" /></template>
