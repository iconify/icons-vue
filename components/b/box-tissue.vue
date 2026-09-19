<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nth9yctlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nth9yctlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:box-tissue" /></template>
