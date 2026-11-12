<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv20yacbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv20yacbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:countly-light" /></template>
