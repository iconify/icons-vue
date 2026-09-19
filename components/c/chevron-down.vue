<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpyid4bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="mpyid4bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:chevron-down" /></template>
