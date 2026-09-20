<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwu39txpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwu39txpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bluesky" /></template>
