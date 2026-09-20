<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb0iq9g5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sb0iq9g5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cups" /></template>
