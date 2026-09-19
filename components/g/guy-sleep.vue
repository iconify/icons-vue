<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv_xycegq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mv_xycegq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-sleep" /></template>
