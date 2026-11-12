<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3xehe9tz.css';
import '../../css/k/koobuxbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x3xehe9tz"/><path class="koobuxbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feeds-fun-light" /></template>
