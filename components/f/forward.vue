<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llc80zbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="llc80zbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:forward" /></template>
