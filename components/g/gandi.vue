<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q92a6obvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q92a6obvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gandi" /></template>
