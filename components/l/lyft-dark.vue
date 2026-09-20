<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzm86-1vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xzm86-1vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lyft-dark" /></template>
