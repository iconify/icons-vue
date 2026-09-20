<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wly3hnkvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wly3hnkvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:call" /></template>
