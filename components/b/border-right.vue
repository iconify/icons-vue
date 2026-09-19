<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltauh_omx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ltauh_omx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-right" /></template>
