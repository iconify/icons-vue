<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr50_qbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vr50_qbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:align-right-2-16" /></template>
