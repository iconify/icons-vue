<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu6inrb8q.css';
import '../../css/o/o4p12ib8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gu6inrb8q"/><path class="o4p12ib8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:charging-station-filled" /></template>
