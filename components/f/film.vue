<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuxx9b2_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kuxx9b2_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:film" /></template>
