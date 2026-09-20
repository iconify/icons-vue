<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok4g82-ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ok4g82-ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hdhomerun-dark" /></template>
