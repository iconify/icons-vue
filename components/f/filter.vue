<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmcj6_b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xmcj6_b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:filter" /></template>
