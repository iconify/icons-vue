<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wworkz96q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wworkz96q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docmost-dark" /></template>
