<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b36ds2bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="b36ds2bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:anomaly-none" /></template>
