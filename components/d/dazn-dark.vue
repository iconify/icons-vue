<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyaxpnb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xyaxpnb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dazn-dark" /></template>
