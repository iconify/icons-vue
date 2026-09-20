<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a485dfc3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a485dfc3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:etsy-light" /></template>
