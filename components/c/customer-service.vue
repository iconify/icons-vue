<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh61ck4mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rh61ck4mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:customer-service" /></template>
