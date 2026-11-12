<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_wgrkdem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_wgrkdem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buggregator-light" /></template>
