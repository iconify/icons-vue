<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt8p0k40b.css';
import '../../css/u/u4b1utgwb.css';
import '../../css/h/hf9tixklt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kt8p0k40b"/><path class="u4b1utgwb"/><path class="hf9tixklt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-direct-link-2-dedicated-hosting" /></template>
