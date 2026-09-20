<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e10jzhbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e10jzhbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-public-proxy-dark" /></template>
