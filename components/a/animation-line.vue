<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbdu-tbiz.css';
import '../../css/v/vtxmsw_ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xbdu-tbiz"/><path class="vtxmsw_ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:animation-line" /></template>
