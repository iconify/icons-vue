<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smu59bb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="smu59bb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hydrus-web-light" /></template>
