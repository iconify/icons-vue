<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i69ysub0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i69ysub0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fedex-light" /></template>
