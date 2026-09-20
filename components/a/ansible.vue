<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncxf18bye.css';
import '../../css/l/ld7aedbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ncxf18bye"/><path class="ld7aedbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ansible" /></template>
