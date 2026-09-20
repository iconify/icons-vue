<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfumhs5dd.css';
import '../../css/n/nsh88-uyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfumhs5dd"/><path class="nsh88-uyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docmost" /></template>
