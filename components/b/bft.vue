<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voxoyd1yc.css';
import '../../css/y/ys14dvbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voxoyd1yc"/><path clip-rule="evenodd" class="ys14dvbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bft" /></template>
