<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmhtbu2jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xmhtbu2jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:compass-1" /></template>
