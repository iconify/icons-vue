<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olgjpxlkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="olgjpxlkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:forward-10" /></template>
