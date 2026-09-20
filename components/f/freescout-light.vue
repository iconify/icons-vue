<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxbz4umia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jxbz4umia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freescout-light" /></template>
