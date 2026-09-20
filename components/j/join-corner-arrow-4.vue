<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l30pv5y8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l30pv5y8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:join-corner-arrow-4" /></template>
