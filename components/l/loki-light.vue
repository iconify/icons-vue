<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y96q7hymd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y96q7hymd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loki-light" /></template>
