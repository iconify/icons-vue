<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxr-fcc-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxr-fcc-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bar-graph-expressive" /></template>
