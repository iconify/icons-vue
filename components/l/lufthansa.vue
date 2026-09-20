<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npskko2ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npskko2ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lufthansa" /></template>
