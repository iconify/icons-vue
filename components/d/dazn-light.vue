<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9-7hdctm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e9-7hdctm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dazn-light" /></template>
