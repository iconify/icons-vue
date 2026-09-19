<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1pj1tb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1pj1tb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-csv" /></template>
