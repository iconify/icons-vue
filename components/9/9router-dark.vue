<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpn7p930p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpn7p930p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:9router-dark" /></template>
