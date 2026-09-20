<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaa_36bkr.css';
import '../../css/x/xa8hyu6ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zaa_36bkr"/><path class="xa8hyu6ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duckduckgo-dark" /></template>
