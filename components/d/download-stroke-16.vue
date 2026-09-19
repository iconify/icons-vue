<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtp_siu6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mtp_siu6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:download-stroke-16" /></template>
