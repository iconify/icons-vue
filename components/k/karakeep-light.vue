<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh1qadn_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xh1qadn_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:karakeep-light" /></template>
