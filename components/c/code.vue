<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf_6m0xwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rf_6m0xwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:code" /></template>
