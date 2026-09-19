<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkcrs2b2j.css';
import '../../css/h/hrklssb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wkcrs2b2j"/><path class="hrklssb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:asset-confirm" /></template>
