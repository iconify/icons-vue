<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ieg6afw1p.css';
import '../../css/a/ak9-x7jxs.css';
import '../../css/x/xz914h8mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ieg6afw1p"/><path class="ak9-x7jxs"/><path class="xz914h8mb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-open-line-duotone" /></template>
