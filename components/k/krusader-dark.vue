<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi3ie_b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wi3ie_b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:krusader-dark" /></template>
