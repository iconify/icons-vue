<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4hx52bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":480};
const content = `<path class="k4hx52bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flip" /></template>
