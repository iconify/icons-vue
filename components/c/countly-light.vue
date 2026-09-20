<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn39y8buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sn39y8buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:countly-light" /></template>
