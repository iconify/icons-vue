<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z601nxboe.css';
import '../../css/s/sh51lircq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z601nxboe"/><path class="sh51lircq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-db2" /></template>
