<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv4dbmbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv4dbmbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowbarr" /></template>
