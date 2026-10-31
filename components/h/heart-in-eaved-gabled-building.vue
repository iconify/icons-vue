<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zers9_rqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zers9_rqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-in-eaved-gabled-building" /></template>
