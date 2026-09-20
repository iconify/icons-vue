<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0j8-xbhn.css';
import '../../css/z/z54z46b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d0j8-xbhn"/><path class="z54z46b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clickhouse" /></template>
