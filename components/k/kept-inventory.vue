<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c815m4b3j.css';
import '../../css/x/xizs9ebfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c815m4b3j"/><path class="xizs9ebfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kept-inventory" /></template>
