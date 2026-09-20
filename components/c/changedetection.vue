<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evtuy-b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="evtuy-b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:changedetection" /></template>
