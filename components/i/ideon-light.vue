<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8m3v-bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8m3v-bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ideon-light" /></template>
