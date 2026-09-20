<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arxe123jq.css';
import '../../css/t/tjw051bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arxe123jq"/><path clip-rule="evenodd" class="tjw051bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-check-circle" /></template>
