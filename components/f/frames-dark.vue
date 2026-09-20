<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie_d5yb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ie_d5yb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frames-dark" /></template>
