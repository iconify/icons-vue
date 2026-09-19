<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2s2ztbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="p2s2ztbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:forward-5" /></template>
