<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub19e0-yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ub19e0-yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bytestash-light" /></template>
