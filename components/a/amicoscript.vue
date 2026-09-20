<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etxd1-exq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etxd1-exq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amicoscript" /></template>
