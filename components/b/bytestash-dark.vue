<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwv0xcc4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kwv0xcc4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bytestash-dark" /></template>
