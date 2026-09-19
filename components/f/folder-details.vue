<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wotujmrpr.css';
import '../../css/s/sm_hxib8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wotujmrpr"/><path class="sm_hxib8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-details" /></template>
