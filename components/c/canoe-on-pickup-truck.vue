<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9hpp2nbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l9hpp2nbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe-on-pickup-truck" /></template>
