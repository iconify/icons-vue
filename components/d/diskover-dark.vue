<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd5g40bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yd5g40bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:diskover-dark" /></template>
