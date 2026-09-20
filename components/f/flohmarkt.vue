<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgtn_5-hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wgtn_5-hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flohmarkt" /></template>
