<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij0d9-bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ij0d9-bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:date-time-2" /></template>
