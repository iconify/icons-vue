<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfcq_3b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lfcq_3b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-chevron-right" /></template>
