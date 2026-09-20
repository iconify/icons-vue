<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj-hv3b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qj-hv3b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adminerevo" /></template>
