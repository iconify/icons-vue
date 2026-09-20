<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9tsge_gb.css';
import '../../css/h/h6ao34een.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9tsge_gb"/><path class="h6ao34een"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:esphome" /></template>
