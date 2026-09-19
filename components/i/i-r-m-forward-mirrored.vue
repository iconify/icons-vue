<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8ni2pbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d8ni2pbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:i-r-m-forward-mirrored" /></template>
