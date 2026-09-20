<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np2o43-0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="np2o43-0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:download-2" /></template>
