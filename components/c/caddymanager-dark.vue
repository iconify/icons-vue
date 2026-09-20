<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w12f35boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w12f35boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caddymanager-dark" /></template>
