<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqd-lj30l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":512};
const content = `<path class="uqd-lj30l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:boiled-egg" /></template>
