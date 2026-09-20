<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoore9bru.css';
import '../../css/a/ailbzjhcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xoore9bru"/><path class="ailbzjhcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-slides-dark" /></template>
