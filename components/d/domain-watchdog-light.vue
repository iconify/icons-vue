<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1_i3l3vn.css';
import '../../css/m/m5lp6jbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="g1_i3l3vn"/><path class="m5lp6jbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-watchdog-light" /></template>
