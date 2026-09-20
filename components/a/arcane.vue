<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4-bqjb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4-bqjb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arcane" /></template>
