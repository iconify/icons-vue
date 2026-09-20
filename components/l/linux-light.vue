<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0xjkpbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n0xjkpbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-light" /></template>
