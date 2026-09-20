<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpju4jbvx.css';
import '../../css/t/tqpmf_bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tpju4jbvx"/><path class="tqpmf_bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hawser-light" /></template>
