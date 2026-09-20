<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6_n2_bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6_n2_bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:diun-dash-light" /></template>
