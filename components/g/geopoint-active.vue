<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-b9rebna.css';
import '../../css/j/j12mv17hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-b9rebna"/><path class="j12mv17hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:geopoint-active" /></template>
