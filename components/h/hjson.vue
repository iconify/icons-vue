<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr445ngfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sr445ngfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hjson" /></template>
