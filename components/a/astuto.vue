<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp1h03ydm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1h03ydm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:astuto" /></template>
