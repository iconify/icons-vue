<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe46s0bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fe46s0bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:box-light" /></template>
