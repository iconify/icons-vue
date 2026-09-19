<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjopgkbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="qjopgkbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:liquor" /></template>
