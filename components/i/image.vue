<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgs0fsb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="wgs0fsb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:image" /></template>
