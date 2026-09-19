<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdeo76mkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pdeo76mkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-round-down" /></template>
