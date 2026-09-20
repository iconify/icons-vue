<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wza49-blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wza49-blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-scale" /></template>
